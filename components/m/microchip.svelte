<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyygioguv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1664};
const content = `<path class="dyygioguv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:microchip" {...props}></Icon>
