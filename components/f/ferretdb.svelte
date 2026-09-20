<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytf1yy1pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ytf1yy1pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ferretdb" {...props}></Icon>
