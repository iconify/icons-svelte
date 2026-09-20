<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uen8fg65q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uen8fg65q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-right-circle-filled" {...props}></Icon>
