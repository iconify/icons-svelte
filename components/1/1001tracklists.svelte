<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcd4ixenp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcd4ixenp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:1001tracklists" {...props}></Icon>
