<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngjilubfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ngjilubfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockpeek-dark" {...props}></Icon>
