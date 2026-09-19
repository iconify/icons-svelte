<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2xscrbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j2xscrbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ae" {...props}></Icon>
