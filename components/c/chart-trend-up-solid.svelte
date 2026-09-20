<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6f6_qben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6f6_qben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-up-solid" {...props}></Icon>
