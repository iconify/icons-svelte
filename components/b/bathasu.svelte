<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xspxmgd4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xspxmgd4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bathasu" {...props}></Icon>
