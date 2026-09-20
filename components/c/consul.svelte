<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyb02xdma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyb02xdma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:consul" {...props}></Icon>
