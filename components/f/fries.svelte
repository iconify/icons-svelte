<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd9m8rbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd9m8rbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:fries" {...props}></Icon>
