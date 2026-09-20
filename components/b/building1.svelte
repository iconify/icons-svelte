<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8wvgabib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8wvgabib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:building1" {...props}></Icon>
