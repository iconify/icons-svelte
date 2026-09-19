<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u65btl1tl.css';
import '../../css/d/dl42-n8go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u65btl1tl"/><path class="dl42-n8go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-circle-half-filled" {...props}></Icon>
