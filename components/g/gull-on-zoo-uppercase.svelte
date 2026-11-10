<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldrvy3bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ldrvy3bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gull-on-zoo-uppercase" {...props}></Icon>
