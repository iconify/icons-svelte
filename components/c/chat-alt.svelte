<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxfil_d2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxfil_d2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chat-alt" {...props}></Icon>
