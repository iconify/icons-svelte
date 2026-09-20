<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd17v2bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jd17v2bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grist-light" {...props}></Icon>
