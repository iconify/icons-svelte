<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-zew7byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-zew7byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:banana-gloss" {...props}></Icon>
