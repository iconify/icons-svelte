<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-lzwbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fk-lzwbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:p5js" {...props}></Icon>
