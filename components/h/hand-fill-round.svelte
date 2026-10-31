<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vige47nfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vige47nfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hand-fill-round" {...props}></Icon>
