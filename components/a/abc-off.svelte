<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueockjdih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueockjdih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:abc-off" {...props}></Icon>
