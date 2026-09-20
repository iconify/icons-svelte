<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmemcjbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmemcjbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-wine" {...props}></Icon>
