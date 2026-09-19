<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agjshx11i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="agjshx11i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:prettier-ignore" {...props}></Icon>
