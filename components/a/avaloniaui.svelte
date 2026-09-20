<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcwzmb8zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcwzmb8zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:avaloniaui" {...props}></Icon>
