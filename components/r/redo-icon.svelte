<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaz_p7cgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaz_p7cgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:redo-icon" {...props}></Icon>
