<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzc6dub2d.css';
import '../../css/f/f7ljz7b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xzc6dub2d"/><path class="f7ljz7b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fish" {...props}></Icon>
