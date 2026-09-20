<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2nx_3s3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2nx_3s3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentofu-dark" {...props}></Icon>
