<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1-rztbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1-rztbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-gloss" {...props}></Icon>
