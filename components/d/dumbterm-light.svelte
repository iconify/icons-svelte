<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lagp55idw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lagp55idw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbterm-light" {...props}></Icon>
