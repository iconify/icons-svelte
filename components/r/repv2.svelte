<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m0hqfh72g.css';
import '../../css/b/bue-ibchr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="m0hqfh72g"/><path class="bue-ibchr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:repv2" {...props}></Icon>
