<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjxex1bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjxex1bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:desktop" {...props}></Icon>
