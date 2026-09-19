<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgu29hljj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lgu29hljj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gitlab" {...props}></Icon>
