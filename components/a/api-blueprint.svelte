<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh5mexb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eh5mexb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:api-blueprint" {...props}></Icon>
