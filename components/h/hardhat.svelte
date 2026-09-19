<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfrkp3b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfrkp3b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:hardhat" {...props}></Icon>
