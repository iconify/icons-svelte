<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4f0g3bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4f0g3bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:laptop" {...props}></Icon>
