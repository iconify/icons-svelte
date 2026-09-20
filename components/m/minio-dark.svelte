<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrvr5sfgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yrvr5sfgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minio-dark" {...props}></Icon>
