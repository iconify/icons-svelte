<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwmqbfb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwmqbfb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-box-outline" {...props}></Icon>
