<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs6pf8bqr.css';
import '../../css/r/rtbfcmafp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cs6pf8bqr"/><path class="rtbfcmafp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-20" {...props}></Icon>
