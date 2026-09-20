<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-dfw_qql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-dfw_qql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkmk-light" {...props}></Icon>
