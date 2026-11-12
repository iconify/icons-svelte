<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch-5d0oph.css';
import '../../css/n/ndg-4phim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ch-5d0oph"/><path class="ndg-4phim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reaparr-light" {...props}></Icon>
