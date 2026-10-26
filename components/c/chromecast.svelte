<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imi4vsbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imi4vsbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chromecast" {...props}></Icon>
