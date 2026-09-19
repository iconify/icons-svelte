<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf9l1q0nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kf9l1q0nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:isidore" {...props}></Icon>
