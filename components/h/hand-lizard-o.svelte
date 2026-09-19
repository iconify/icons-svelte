<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-xm_j6rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="q-xm_j6rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-lizard-o" {...props}></Icon>
