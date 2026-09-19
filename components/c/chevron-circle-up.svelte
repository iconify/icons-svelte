<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubs-d4r4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ubs-d4r4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chevron-circle-up" {...props}></Icon>
