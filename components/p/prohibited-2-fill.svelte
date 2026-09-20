<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-924ac3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-924ac3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:prohibited-2-fill" {...props}></Icon>
