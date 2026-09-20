<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqm-8rbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqm-8rbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ink-outline" {...props}></Icon>
