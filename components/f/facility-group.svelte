<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1a17le6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u1a17le6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:facility-group" {...props}></Icon>
