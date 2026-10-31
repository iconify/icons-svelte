<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d82fz4w8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d82fz4w8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-check-fill-round" {...props}></Icon>
