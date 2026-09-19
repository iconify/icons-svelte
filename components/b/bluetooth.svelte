<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azqwpqbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="azqwpqbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bluetooth" {...props}></Icon>
