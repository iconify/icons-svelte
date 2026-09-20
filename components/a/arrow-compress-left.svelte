<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e83fdyu4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e83fdyu4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-compress-left" {...props}></Icon>
