<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shx8lpdkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shx8lpdkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bytestash-dark" {...props}></Icon>
