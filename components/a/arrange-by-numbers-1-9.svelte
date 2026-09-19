<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ardd9_bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ardd9_bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange-by-numbers-1-9" {...props}></Icon>
