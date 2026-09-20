<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6a_bmqya.css';
import '../../css/r/r5ot870ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6a_bmqya"/><path class="r5ot870ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notepad-plus-plus-light" {...props}></Icon>
