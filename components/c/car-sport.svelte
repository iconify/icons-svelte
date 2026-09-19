<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qou-94boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qou-94boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:car-sport" {...props}></Icon>
