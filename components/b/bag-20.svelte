<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oora6eb1h.css';
import '../../css/l/l0_kzwbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oora6eb1h"/><path class="l0_kzwbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bag-20" {...props}></Icon>
