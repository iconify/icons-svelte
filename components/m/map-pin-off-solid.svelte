<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcm9-cbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcm9-cbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-off-solid" {...props}></Icon>
