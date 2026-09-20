<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgwq21n2c.css';
import '../../css/g/g4las-uut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lgwq21n2c"/><path class="g4las-uut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-graphic-tablet" {...props}></Icon>
