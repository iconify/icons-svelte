<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvu3ibcnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvu3ibcnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnipoly-light" {...props}></Icon>
