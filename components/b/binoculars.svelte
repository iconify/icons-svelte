<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l815gt00n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l815gt00n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:binoculars" {...props}></Icon>
