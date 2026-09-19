<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygjwjl6cp.css';
import '../../css/j/j15unt4yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ygjwjl6cp"/><path class="j15unt4yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pyscript-wordmark" {...props}></Icon>
