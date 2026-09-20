<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtwpjkb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtwpjkb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jellyfin" {...props}></Icon>
