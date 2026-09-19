<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1klr8o9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u1klr8o9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bitcoin" {...props}></Icon>
