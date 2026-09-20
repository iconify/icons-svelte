<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3991bcxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="f3991bcxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:indent-increase" {...props}></Icon>
