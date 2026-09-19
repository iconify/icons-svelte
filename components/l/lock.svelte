<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjt7k-myh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjt7k-myh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:lock" {...props}></Icon>
