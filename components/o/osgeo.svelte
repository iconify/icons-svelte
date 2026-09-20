<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewr23_bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewr23_bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:osgeo" {...props}></Icon>
