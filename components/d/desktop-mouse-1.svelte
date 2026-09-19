<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os1b52jwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os1b52jwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:desktop-mouse-1" {...props}></Icon>
