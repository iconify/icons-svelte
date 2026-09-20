<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmubv-bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmubv-bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-wireless-outline" {...props}></Icon>
