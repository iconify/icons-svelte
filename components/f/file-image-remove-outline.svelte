<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf1aab8sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1aab8sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-remove-outline" {...props}></Icon>
