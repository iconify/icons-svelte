<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg2x72bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg2x72bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-down" {...props}></Icon>
