<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd66evbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nd66evbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lancommander-dark" {...props}></Icon>
