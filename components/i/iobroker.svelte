<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2lhupbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2lhupbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iobroker" {...props}></Icon>
