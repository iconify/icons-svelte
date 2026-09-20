<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do7ealbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="do7ealbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-down-outline" {...props}></Icon>
