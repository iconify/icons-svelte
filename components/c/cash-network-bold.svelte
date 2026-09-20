<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wokb92bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wokb92bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cash-network-bold" {...props}></Icon>
