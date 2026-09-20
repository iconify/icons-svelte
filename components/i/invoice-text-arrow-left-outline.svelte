<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9d33dyrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9d33dyrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-arrow-left-outline" {...props}></Icon>
