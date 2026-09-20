<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9fln6bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c9fln6bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-light" {...props}></Icon>
