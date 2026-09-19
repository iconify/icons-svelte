<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo4xqf7hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zo4xqf7hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:ejs" {...props}></Icon>
