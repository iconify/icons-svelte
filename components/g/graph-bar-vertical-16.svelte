<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgvc3bknt.css';
import '../../css/n/nmc_ieezo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tgvc3bknt"/><path class="nmc_ieezo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-bar-vertical-16" {...props}></Icon>
