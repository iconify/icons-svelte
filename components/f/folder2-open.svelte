<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtadfcbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qtadfcbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:folder2-open" {...props}></Icon>
