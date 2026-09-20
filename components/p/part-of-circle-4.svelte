<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duchhy63s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="duchhy63s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle-4" {...props}></Icon>
