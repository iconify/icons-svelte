<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8lmigbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8lmigbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-success" {...props}></Icon>
