<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4t-70uyr.css';
import '../../css/v/vfekuobce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4t-70uyr"/><path class="vfekuobce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailflow-sh" {...props}></Icon>
