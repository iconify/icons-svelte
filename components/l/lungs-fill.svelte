<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5c9r5brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w5c9r5brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:lungs-fill" {...props}></Icon>
