<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v99dkbc9l.css';
import '../../css/l/ltc2--b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v99dkbc9l"/><path class="ltc2--b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-bottle-20" {...props}></Icon>
