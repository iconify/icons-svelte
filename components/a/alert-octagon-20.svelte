<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrdv28bdf.css';
import '../../css/v/vceel18zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mrdv28bdf"/><path class="vceel18zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-octagon-20" {...props}></Icon>
