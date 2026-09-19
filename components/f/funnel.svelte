<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4jpy0b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d4jpy0b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:funnel" {...props}></Icon>
