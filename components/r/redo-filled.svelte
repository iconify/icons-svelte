<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3zp72brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3zp72brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:redo-filled" {...props}></Icon>
