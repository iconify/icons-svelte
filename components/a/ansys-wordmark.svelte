<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvbkgeawu.css';
import '../../css/y/y87l3m6qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pvbkgeawu"/><path class="y87l3m6qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ansys-wordmark" {...props}></Icon>
