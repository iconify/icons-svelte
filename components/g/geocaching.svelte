<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wysf0yo7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wysf0yo7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:geocaching" {...props}></Icon>
