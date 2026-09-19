<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpimwccis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kpimwccis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pump-medical" {...props}></Icon>
