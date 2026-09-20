<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5y0zvbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5y0zvbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ring" {...props}></Icon>
