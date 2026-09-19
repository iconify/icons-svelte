<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhnivs28x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="mhnivs28x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-amex" {...props}></Icon>
