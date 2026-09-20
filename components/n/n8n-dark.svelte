<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qolt9gbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qolt9gbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:n8n-dark" {...props}></Icon>
