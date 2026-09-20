<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsl8n1rvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsl8n1rvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bootstrap-line" {...props}></Icon>
