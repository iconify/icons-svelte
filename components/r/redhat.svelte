<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfb64bla.css';
import '../../css/k/kbh20vd3x.css';
import '../../css/m/mexzrqjpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fzfb64bla"/><path class="kbh20vd3x"/><path class="mexzrqjpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:redhat" {...props}></Icon>
