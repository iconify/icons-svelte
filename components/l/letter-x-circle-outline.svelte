<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/samu3ccav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="samu3ccav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-x-circle-outline" {...props}></Icon>
