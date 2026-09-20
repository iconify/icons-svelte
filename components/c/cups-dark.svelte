<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb0iq9g5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sb0iq9g5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cups-dark" {...props}></Icon>
