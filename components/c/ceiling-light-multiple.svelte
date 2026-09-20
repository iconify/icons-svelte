<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdkf4bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdkf4bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ceiling-light-multiple" {...props}></Icon>
