<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dam6tqlqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dam6tqlqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:registered" {...props}></Icon>
