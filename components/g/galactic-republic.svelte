<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si7_7aceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="si7_7aceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:galactic-republic" {...props}></Icon>
