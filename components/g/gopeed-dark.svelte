<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki1q34b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ki1q34b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gopeed-dark" {...props}></Icon>
