<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc_vo_1qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc_vo_1qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:laptop-download-filled" {...props}></Icon>
