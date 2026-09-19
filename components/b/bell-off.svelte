<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikf5vpbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikf5vpbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bell-off" {...props}></Icon>
