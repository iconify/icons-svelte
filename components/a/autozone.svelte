<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1t2i0p0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1t2i0p0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autozone" {...props}></Icon>
