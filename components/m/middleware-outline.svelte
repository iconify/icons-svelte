<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi5qpp_-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi5qpp_-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:middleware-outline" {...props}></Icon>
