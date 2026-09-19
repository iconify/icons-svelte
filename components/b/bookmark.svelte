<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6231zisq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="k6231zisq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:bookmark" {...props}></Icon>
