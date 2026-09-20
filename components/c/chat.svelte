<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm8m2gi0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm8m2gi0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat" {...props}></Icon>
