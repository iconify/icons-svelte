<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asbux8b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asbux8b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-gloss" {...props}></Icon>
