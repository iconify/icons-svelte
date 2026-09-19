<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz06rjcob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jz06rjcob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:booty" {...props}></Icon>
