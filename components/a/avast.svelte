<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aza816-6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aza816-6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avast" {...props}></Icon>
