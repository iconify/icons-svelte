<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a35ioxuoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a35ioxuoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-down-square" {...props}></Icon>
