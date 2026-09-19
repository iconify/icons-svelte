<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvnle8i8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uvnle8i8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-breakpoint-data-unverified" {...props}></Icon>
