<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv6rri-bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nv6rri-bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:list-circle" {...props}></Icon>
