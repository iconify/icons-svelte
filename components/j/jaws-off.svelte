<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je12_vbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je12_vbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jaws-off" {...props}></Icon>
