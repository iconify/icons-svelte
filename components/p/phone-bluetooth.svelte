<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmi8ijf7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="dmi8ijf7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-bluetooth" {...props}></Icon>
