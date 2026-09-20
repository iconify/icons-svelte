<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d07mmikoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d07mmikoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:add-call" {...props}></Icon>
