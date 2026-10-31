<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsy5oy3nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsy5oy3nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:accessibility-gloss" {...props}></Icon>
