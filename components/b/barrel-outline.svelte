<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpgb8bbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpgb8bbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:barrel-outline" {...props}></Icon>
