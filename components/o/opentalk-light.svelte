<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vicm532xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vicm532xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentalk-light" {...props}></Icon>
