<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm895ybek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm895ybek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrows-circle-counterclockwise-expressive" {...props}></Icon>
