<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu_ys67gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nu_ys67gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:baloon" {...props}></Icon>
