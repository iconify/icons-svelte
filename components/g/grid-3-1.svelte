<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbrq33b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbrq33b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:grid-3-1" {...props}></Icon>
