<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubh594mea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ubh594mea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:matic" {...props}></Icon>
