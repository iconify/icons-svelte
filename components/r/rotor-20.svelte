<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zipe_1bgb.css';
import '../../css/w/w2ey4wbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zipe_1bgb"/><path class="w2ey4wbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotor-20" {...props}></Icon>
