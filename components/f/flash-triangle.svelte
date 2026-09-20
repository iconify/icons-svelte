<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7bgk8b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7bgk8b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-triangle" {...props}></Icon>
