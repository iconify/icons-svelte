<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp6hdkbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6hdkbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:photo-album-filled" {...props}></Icon>
