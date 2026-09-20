<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f063dbdeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f063dbdeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-lock-open" {...props}></Icon>
