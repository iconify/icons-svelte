<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlat7iboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dlat7iboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cart-badge-plus" {...props}></Icon>
