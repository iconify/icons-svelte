<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ct_9bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1056,"height":1408};
const content = `<g transform="translate(0 1408) scale(1 -1)"><path class="t3ct_9bhw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:level-down" {...props}></Icon>
