<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdnfh3lyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdnfh3lyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:latex" {...props}></Icon>
