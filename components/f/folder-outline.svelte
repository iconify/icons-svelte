<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf4k8s7-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4k8s7-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-outline" {...props}></Icon>
