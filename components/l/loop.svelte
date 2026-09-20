<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi5cw-bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi5cw-bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:loop" {...props}></Icon>
