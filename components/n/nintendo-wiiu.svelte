<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j57f-3ujj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j57f-3ujj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nintendo-wiiu" {...props}></Icon>
