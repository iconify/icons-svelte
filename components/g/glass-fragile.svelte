<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa3u_sbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3u_sbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-fragile" {...props}></Icon>
