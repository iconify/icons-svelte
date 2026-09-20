<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb2hu2lmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tb2hu2lmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:download" {...props}></Icon>
