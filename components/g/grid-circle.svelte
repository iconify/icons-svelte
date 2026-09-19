<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipn51glyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ipn51glyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:grid-circle" {...props}></Icon>
