<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6z27mruz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6z27mruz wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mail-open-gloss" {...props}></Icon>
