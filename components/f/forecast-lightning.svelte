<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf_710lax.css';
import '../../css/o/o-x0dsblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yf_710lax"/><path class="o-x0dsblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:forecast-lightning" {...props}></Icon>
