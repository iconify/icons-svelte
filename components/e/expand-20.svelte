<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0np8zw3o.css';
import '../../css/f/f7tmn3bfb.css';
import '../../css/q/qohosibzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h0np8zw3o"/><path class="f7tmn3bfb"/><path class="qohosibzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:expand-20" {...props}></Icon>
