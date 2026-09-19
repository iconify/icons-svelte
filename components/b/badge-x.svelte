<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8nnhdc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8nnhdc8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:badge-x" {...props}></Icon>
