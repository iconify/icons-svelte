<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj4fatbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pj4fatbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:h-expand" {...props}></Icon>
