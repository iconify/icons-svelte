<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvub7-qvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvub7-qvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cube-sharp" {...props}></Icon>
