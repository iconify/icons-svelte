<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2yhh17rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u2yhh17rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:restart" {...props}></Icon>
