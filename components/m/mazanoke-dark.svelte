<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k60j8oblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k60j8oblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mazanoke-dark" {...props}></Icon>
