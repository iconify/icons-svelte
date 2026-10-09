<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqdl70b_g.css';
import '../../css/s/st9n28bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nqdl70b_g"/><path class="st9n28bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fridge-20" {...props}></Icon>
