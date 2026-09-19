<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucjk_d2la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucjk_d2la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:glass" {...props}></Icon>
