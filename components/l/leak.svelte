<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4l6zw40o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4l6zw40o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:leak" {...props}></Icon>
