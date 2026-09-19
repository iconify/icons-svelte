<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugt25bbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugt25bbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:ice-cream" {...props}></Icon>
