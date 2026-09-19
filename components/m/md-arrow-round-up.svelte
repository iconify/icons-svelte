<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rum1esb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rum1esb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-round-up" {...props}></Icon>
