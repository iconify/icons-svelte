<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f87i2j8hs.css';
import '../../css/b/bo_tdpbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f87i2j8hs"/><circle class="bo_tdpbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:moonrepo" {...props}></Icon>
