<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12ji_bzg.css';
import '../../css/a/azfjht1_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="azfjht1_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-javascript-open" {...props}></Icon>
