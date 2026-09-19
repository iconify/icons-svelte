<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbia38xlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mbia38xlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:emacs" {...props}></Icon>
