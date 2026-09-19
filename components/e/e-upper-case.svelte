<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/benkryb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":735};
const content = `<path class="benkryb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:e-upper-case" {...props}></Icon>
