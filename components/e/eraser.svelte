<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amz719bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amz719bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:eraser" {...props}></Icon>
