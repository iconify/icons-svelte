<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfq1gi_xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfq1gi_xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-refresh" {...props}></Icon>
