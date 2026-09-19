<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iksa7qb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iksa7qb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mkr" {...props}></Icon>
