<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvus91o1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvus91o1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:adchoices" {...props}></Icon>
