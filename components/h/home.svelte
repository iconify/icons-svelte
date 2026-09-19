<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1cokcivi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="z1cokcivi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:home" {...props}></Icon>
