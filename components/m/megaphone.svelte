<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqpu1tbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqpu1tbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:megaphone" {...props}></Icon>
