<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rif_rfbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rif_rfbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hitachi" {...props}></Icon>
