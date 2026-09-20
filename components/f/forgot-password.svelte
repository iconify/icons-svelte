<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anudjl__q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anudjl__q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forgot-password" {...props}></Icon>
