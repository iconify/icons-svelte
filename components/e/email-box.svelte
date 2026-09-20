<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzgpirban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzgpirban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-box" {...props}></Icon>
