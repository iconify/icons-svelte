<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7bnwpbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7bnwpbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:currency-dollar" {...props}></Icon>
