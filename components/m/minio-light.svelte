<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqfdm7snc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sqfdm7snc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minio-light" {...props}></Icon>
