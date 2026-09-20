<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok4g82-ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ok4g82-ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hdhomerun-dark" {...props}></Icon>
