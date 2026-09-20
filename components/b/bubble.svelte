<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsp0khbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dsp0khbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bubble" {...props}></Icon>
