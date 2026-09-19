<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov2syn0_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":760,"height":850};
const content = `<path class="ov2syn0_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:dribbble" {...props}></Icon>
