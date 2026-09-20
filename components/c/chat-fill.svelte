<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djq87ob_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djq87ob_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chat-fill" {...props}></Icon>
