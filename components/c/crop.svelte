<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7baubbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7baubbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:crop" {...props}></Icon>
