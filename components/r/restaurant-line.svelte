<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsl39u34c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsl39u34c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restaurant-line" {...props}></Icon>
