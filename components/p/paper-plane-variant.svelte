<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywt1lbbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywt1lbbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paper-plane-variant" {...props}></Icon>
