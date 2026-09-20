<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo_c-qbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_c-qbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-off-outline" {...props}></Icon>
