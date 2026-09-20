<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfkgd6bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nfkgd6bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freebsd" {...props}></Icon>
