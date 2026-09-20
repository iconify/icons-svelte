<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf66cyj2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cf66cyj2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filestash-dark" {...props}></Icon>
