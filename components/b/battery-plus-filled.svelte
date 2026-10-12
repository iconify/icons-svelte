<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz3zj39wl.css';
import '../../css/m/m-jnejbbp.css';
import '../../css/f/fdgucpbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz3zj39wl"/><path clip-rule="evenodd" class="m-jnejbbp"/><path class="fdgucpbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:battery-plus-filled" {...props}></Icon>
