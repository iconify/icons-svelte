<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu9wddprx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bu9wddprx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-down-circle" {...props}></Icon>
