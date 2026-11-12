<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn1fsybwx.css';
import '../../css/u/u4tpbbpvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn1fsybwx"/><path class="u4tpbbpvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minio" {...props}></Icon>
