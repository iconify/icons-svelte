<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9rr8m5nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9rr8m5nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:code-climate" {...props}></Icon>
