<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-_lcbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gb-_lcbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:html" {...props}></Icon>
