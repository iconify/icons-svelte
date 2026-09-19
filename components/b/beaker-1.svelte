<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdish1bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdish1bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:beaker-1" {...props}></Icon>
