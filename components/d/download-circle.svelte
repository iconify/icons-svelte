<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiclth24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiclth24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-circle" {...props}></Icon>
