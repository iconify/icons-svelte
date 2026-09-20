<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_rlegggo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_rlegggo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-filled" {...props}></Icon>
