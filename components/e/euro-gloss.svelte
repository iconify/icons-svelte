<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqu884bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqu884bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:euro-gloss" {...props}></Icon>
