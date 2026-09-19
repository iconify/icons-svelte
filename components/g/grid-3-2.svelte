<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5h_42yze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5h_42yze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:grid-3-2" {...props}></Icon>
