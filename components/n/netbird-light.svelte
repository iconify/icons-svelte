<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md2-6kbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md2-6kbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netbird-light" {...props}></Icon>
