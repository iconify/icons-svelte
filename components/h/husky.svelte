<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0mwq287o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x0mwq287o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:husky" {...props}></Icon>
