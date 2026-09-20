<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_fb6mbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_fb6mbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-social-dark" {...props}></Icon>
