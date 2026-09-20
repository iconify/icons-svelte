<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzshpccwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzshpccwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lancommander" {...props}></Icon>
