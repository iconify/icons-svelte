<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uie78-bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uie78-bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-hearts-line" {...props}></Icon>
