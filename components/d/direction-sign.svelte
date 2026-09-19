<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsszjbc5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="xsszjbc5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:direction-sign" {...props}></Icon>
