<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq7alcpun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rq7alcpun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:heart-circle-bolt" {...props}></Icon>
