<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhyol_beh.css';
import '../../css/r/r3s9vk_bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uhyol_beh"/><path class="r3s9vk_bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gleam" {...props}></Icon>
