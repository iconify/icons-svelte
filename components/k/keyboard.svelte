<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k665-1bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="k665-1bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:keyboard" {...props}></Icon>
