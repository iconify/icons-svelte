<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3qx5ernl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3qx5ernl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:az-sort-descending-letters-line" {...props}></Icon>
