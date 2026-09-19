<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l617jztlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l617jztlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:inbox" {...props}></Icon>
