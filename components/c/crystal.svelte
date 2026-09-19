<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cizxf3pgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cizxf3pgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:crystal" {...props}></Icon>
