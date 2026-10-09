<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mcems0k.css';
import '../../css/d/ddxx92y4s.css';
import '../../css/a/ampqdu6-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="ddxx92y4s"/><path class="ampqdu6-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-battery-20-bold" {...props}></Icon>
