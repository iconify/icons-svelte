<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxrfocm_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxrfocm_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-off-outline" {...props}></Icon>
