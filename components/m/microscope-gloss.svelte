<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbgj9ebag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgj9ebag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microscope-gloss" {...props}></Icon>
