<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_0t79bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="p_0t79bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hammer" {...props}></Icon>
