<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wphz0abhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wphz0abhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:insert-row-top" {...props}></Icon>
