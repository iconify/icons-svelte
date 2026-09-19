<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o91nh_bfw.css';
import '../../css/h/h8fdi9bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o91nh_bfw"/><path class="h8fdi9bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:man-sharp" {...props}></Icon>
