<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpb7l4b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tpb7l4b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-3x3-gap-fill" {...props}></Icon>
