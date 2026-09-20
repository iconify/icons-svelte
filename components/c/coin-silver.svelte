<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvn9to28b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="kvn9to28b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:coin-silver" {...props}></Icon>
