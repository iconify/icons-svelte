<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1_dngb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1_dngb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:cloud-moon" {...props}></Icon>
