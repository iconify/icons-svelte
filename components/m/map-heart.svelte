<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv_iads2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv_iads2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-heart" {...props}></Icon>
