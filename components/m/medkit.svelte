<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zop99obdj.css';
import '../../css/d/d0iebyb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zop99obdj"/><path class="d0iebyb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:medkit" {...props}></Icon>
