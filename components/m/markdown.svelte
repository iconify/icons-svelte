<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn683-7jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tn683-7jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:markdown" {...props}></Icon>
