<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy-pc_6xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iy-pc_6xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-grid-1x2" {...props}></Icon>
