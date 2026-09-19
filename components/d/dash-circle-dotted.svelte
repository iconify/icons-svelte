<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8z9m34ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8z9m34ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dash-circle-dotted" {...props}></Icon>
