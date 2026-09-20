<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjiluybel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjiluybel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fantasy-variant" {...props}></Icon>
