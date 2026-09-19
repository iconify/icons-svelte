<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dip7kslof.css';
import '../../css/t/t55-6mljh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dip7kslof"/><path class="t55-6mljh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-check" {...props}></Icon>
