<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8-7f6bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-7f6bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-double-right" {...props}></Icon>
