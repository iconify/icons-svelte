<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8l8khb2z.css';
import '../../css/u/uuh2v9f7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l8l8khb2z"/><path class="uuh2v9f7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:bash" {...props}></Icon>
