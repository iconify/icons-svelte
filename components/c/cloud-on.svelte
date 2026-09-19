<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr4d2z28y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr4d2z28y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:cloud-on" {...props}></Icon>
