<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8r1xw6ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8r1xw6ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-temperature" {...props}></Icon>
