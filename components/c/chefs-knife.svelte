<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7j76tezx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e7j76tezx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chefs-knife" {...props}></Icon>
