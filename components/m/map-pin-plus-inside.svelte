<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbc5s7bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc5s7bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-plus-inside" {...props}></Icon>
