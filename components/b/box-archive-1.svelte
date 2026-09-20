<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rva00qbbz.css';
import '../../css/j/jii8hcxej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="rva00qbbz"/><path class="jii8hcxej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:box-archive-1" {...props}></Icon>
