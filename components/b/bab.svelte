<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5l85hbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p5l85hbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bab" {...props}></Icon>
