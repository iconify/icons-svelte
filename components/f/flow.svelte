<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiu6qlb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":413,"height":512};
const content = `<path class="wiu6qlb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:flow" {...props}></Icon>
