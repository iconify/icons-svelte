<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhp8iwb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp8iwb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-line" {...props}></Icon>
