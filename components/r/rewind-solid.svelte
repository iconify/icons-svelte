<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slhz6db9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slhz6db9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rewind-solid" {...props}></Icon>
