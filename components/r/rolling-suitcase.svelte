<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8v1rm3bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8v1rm3bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:rolling-suitcase" {...props}></Icon>
