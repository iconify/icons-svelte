<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo0-p2b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo0-p2b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:brand-instagram" {...props}></Icon>
