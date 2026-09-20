<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzn2_3byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vzn2_3byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-keyboard-wireless" {...props}></Icon>
