<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itx6pdwsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itx6pdwsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gstreamer" {...props}></Icon>
