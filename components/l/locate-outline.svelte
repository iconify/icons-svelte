<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f43p7lhjp.css';
import '../../css/l/lbpp58r_m.css';
import '../../css/d/dc686_elh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f43p7lhjp"/><path class="lbpp58r_m"/><path class="dc686_elh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:locate-outline" {...props}></Icon>
