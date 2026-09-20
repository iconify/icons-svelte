<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msr53udzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="msr53udzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-iris-scan" {...props}></Icon>
