<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz274dbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pz274dbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dagu-light" {...props}></Icon>
