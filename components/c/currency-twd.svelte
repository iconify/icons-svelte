<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czfpedcvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czfpedcvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-twd" {...props}></Icon>
