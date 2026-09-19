<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbrtfx9pu.css';
import '../../css/s/s9jq5ybcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrtfx9pu"/><path class="s9jq5ybcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-plus" {...props}></Icon>
