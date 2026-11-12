<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaebx0bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaebx0bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agam-space-light" {...props}></Icon>
