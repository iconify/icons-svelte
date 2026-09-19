<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osa9y-bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="osa9y-bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:notifications" {...props}></Icon>
