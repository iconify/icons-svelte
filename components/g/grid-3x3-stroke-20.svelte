<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clczj4b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="clczj4b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-3x3-stroke-20" {...props}></Icon>
