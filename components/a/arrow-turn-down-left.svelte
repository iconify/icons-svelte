<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0i42zhal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w0i42zhal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-down-left" {...props}></Icon>
