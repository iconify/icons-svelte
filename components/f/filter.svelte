<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6kqmgbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u6kqmgbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:filter" {...props}></Icon>
