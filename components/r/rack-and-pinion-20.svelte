<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh5sn9n9c.css';
import '../../css/d/d1xxgk97m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qh5sn9n9c"/><path class="d1xxgk97m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rack-and-pinion-20" {...props}></Icon>
