<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oawkc0bme.css';
import '../../css/e/esmev4g_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oawkc0bme"/><path class="esmev4g_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-20" {...props}></Icon>
