<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn896ebbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":201,"height":201};
const content = `<path class="dn896ebbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:imba" {...props}></Icon>
