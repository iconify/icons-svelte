<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlzprl1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlzprl1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-radius" {...props}></Icon>
