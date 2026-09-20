<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddd-_cb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddd-_cb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-minus-cursor" {...props}></Icon>
