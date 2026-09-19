<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3n1rsjez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f3n1rsjez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:map" {...props}></Icon>
