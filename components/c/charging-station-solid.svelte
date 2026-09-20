<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2p352fxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o2p352fxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:charging-station-solid" {...props}></Icon>
