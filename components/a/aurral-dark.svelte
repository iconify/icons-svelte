<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5whyy_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl5whyy_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aurral-dark" {...props}></Icon>
