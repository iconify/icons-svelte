<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe1boo_8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe1boo_8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-add" {...props}></Icon>
