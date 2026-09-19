<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd78m2pfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nd78m2pfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpup" {...props}></Icon>
