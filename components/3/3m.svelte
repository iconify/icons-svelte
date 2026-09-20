<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oevl31bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oevl31bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:3m" {...props}></Icon>
