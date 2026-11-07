<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j8ful4bxb.css';
import '../../css/r/ryhgqrraa.css';
import '../../css/v/v7q1lwidl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j8ful4bxb"/><path class="ryhgqrraa"/><path class="v7q1lwidl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-broken" {...props}></Icon>
