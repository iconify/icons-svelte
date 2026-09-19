<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc2gdbbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc2gdbbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:patreon" {...props}></Icon>
