<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk4_gdckq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fk4_gdckq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud-showers-heavy" {...props}></Icon>
