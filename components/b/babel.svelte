<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz00n171p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iz00n171p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:babel" {...props}></Icon>
