<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0_0luk2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0_0luk2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:programming-code" {...props}></Icon>
