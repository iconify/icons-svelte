<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1soy6buh.css';
import '../../css/c/cbl4o-biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r1soy6buh"/><path class="cbl4o-biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kaldi" {...props}></Icon>
