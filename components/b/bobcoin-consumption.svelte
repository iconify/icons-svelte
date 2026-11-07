<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsna8m2xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nsna8m2xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bobcoin-consumption" {...props}></Icon>
