<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i791vdbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i791vdbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bland-altman-plot" {...props}></Icon>
