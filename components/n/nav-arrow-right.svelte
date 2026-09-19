<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs9ntbb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9ntbb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:nav-arrow-right" {...props}></Icon>
