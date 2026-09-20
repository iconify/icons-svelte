<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd040z9hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xd040z9hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnipoly-light" {...props}></Icon>
