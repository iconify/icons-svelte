<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o91nh_bfw.css';
import '../../css/b/b500pmbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o91nh_bfw"/><path class="b500pmbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:body-sharp" {...props}></Icon>
