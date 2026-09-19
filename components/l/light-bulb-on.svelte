<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nio8jccck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nio8jccck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:light-bulb-on" {...props}></Icon>
