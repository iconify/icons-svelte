<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n30rbnbif.css';
import '../../css/g/g13wum06j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n30rbnbif"/><path class="g13wum06j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailpit-light" {...props}></Icon>
