<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz131qbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oz131qbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:left-arrow-circle" {...props}></Icon>
