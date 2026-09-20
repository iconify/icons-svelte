<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpb3pvb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpb3pvb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minio-light" {...props}></Icon>
