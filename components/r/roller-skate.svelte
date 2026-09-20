<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxzkr4y1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxzkr4y1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roller-skate" {...props}></Icon>
