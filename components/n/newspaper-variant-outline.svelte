<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yulxvacom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yulxvacom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:newspaper-variant-outline" {...props}></Icon>
