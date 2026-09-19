<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbsk2ebxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hbsk2ebxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:horse" {...props}></Icon>
