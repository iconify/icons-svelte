<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzktj7b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nzktj7b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:mermaid" {...props}></Icon>
