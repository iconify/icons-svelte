<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr8bfngly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr8bfngly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:fast-forward-gloss" {...props}></Icon>
