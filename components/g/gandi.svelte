<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtr5qkmsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtr5qkmsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gandi" {...props}></Icon>
