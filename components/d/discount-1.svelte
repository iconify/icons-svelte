<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iohkho2qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iohkho2qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:discount-1" {...props}></Icon>
