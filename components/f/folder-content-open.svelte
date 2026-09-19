<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12ji_bzg.css';
import '../../css/a/a5g1qzb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="a5g1qzb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-content-open" {...props}></Icon>
