<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix7slo6_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ix7slo6_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowshape-turn-up-right" {...props}></Icon>
