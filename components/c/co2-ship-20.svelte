<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze_xj8buq.css';
import '../../css/u/uu-b3jbqp.css';
import '../../css/i/iktbjzb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ze_xj8buq"/><path class="uu-b3jbqp"/><path class="iktbjzb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-ship-20" {...props}></Icon>
