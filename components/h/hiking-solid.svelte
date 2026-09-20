<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uabfv_bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uabfv_bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hiking-solid" {...props}></Icon>
