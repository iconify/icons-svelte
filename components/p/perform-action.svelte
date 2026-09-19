<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhdj6ccwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhdj6ccwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:perform-action" {...props}></Icon>
