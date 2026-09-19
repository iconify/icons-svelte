<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xem2oro9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xem2oro9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:paper-plane" {...props}></Icon>
