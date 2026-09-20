<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe38t4jqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oe38t4jqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radicale-light" {...props}></Icon>
