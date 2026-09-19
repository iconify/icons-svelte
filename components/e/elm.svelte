<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n96tplo5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n96tplo5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:elm" {...props}></Icon>
