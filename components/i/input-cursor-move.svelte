<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iypbzcy7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iypbzcy7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:input-cursor-move" {...props}></Icon>
