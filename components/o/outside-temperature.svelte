<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q15dvpbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q15dvpbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:outside-temperature" {...props}></Icon>
