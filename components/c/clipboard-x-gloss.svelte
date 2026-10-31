<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi8-l0bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi8-l0bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-x-gloss" {...props}></Icon>
