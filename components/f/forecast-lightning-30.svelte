<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kznva-0mg.css';
import '../../css/g/gvmh5mbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kznva-0mg"/><path class="gvmh5mbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:forecast-lightning-30" {...props}></Icon>
