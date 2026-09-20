<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndkix9b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndkix9b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:music-1-filled" {...props}></Icon>
