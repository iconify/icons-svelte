<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhpgbabpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhpgbabpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cursor-light" {...props}></Icon>
