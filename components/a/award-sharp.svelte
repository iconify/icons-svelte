<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd2iq_8mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd2iq_8mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:award-sharp" {...props}></Icon>
