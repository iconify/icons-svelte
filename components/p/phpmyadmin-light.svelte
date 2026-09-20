<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncc_k81kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncc_k81kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpmyadmin-light" {...props}></Icon>
