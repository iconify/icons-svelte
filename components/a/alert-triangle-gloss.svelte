<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8wzu_1ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8wzu_1ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alert-triangle-gloss" {...props}></Icon>
