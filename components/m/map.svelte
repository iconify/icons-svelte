<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8-m1_6ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8-m1_6ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:map" {...props}></Icon>
