<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp0t9zbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vp0t9zbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:hand-point-left" {...props}></Icon>
