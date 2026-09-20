<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfgcmz94w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfgcmz94w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-right-down-line" {...props}></Icon>
