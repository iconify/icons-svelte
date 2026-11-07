<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v7q1lwidl.css';
import '../../css/r/r2yb3pnfd.css';
import '../../css/r/ryhgqrraa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v7q1lwidl"/><path class="r2yb3pnfd"/><path class="ryhgqrraa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-linear" {...props}></Icon>
