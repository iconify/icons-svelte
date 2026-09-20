<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q25l8gb6x.css';
import '../../css/y/yac-066cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q25l8gb6x"/><path class="yac-066cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-action-location-1-bold" {...props}></Icon>
