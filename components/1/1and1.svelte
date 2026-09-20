<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-5-hx-wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-5-hx-wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:1and1" {...props}></Icon>
