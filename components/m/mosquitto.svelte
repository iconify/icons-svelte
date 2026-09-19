<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y52du4bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y52du4bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mosquitto" {...props}></Icon>
