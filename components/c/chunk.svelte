<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1c-26sug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="z1c-26sug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chunk" {...props}></Icon>
