<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2poz0bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2poz0bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dropbox-dark" {...props}></Icon>
