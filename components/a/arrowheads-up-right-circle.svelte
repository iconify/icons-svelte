<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6-k0_bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f6-k0_bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-right-circle" {...props}></Icon>
