<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d75b1zbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d75b1zbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:minimize-1" {...props}></Icon>
