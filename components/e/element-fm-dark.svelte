<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9-_4zbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9-_4zbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:element-fm-dark" {...props}></Icon>
