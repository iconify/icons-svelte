<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp21e2hbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fp21e2hbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:chips" {...props}></Icon>
