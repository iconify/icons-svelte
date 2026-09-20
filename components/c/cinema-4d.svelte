<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq23ysbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq23ysbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cinema-4d" {...props}></Icon>
