<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrq_0iqap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nrq_0iqap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:minimize-stroke-12" {...props}></Icon>
