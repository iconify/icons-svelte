<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxl6bezbx.css';
import '../../css/z/zzvwx-xsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yxl6bezbx"/><path class="wm-a zzvwx-xsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-arrow-down" {...props}></Icon>
