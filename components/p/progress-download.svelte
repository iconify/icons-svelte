<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_vip7hyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_vip7hyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-download" {...props}></Icon>
