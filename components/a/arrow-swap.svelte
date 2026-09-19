<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnh568b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hnh568b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-swap" {...props}></Icon>
