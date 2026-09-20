<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmi07ebkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmi07ebkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-reel" {...props}></Icon>
