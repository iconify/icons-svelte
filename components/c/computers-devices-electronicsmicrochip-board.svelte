<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjj25p_6s.css';
import '../../css/m/m4c745b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vjj25p_6s"/><path class="m4c745b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronicsmicrochip-board" {...props}></Icon>
