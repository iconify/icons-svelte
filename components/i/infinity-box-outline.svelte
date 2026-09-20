<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1a8l432h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1a8l432h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:infinity-box-outline" {...props}></Icon>
