<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjm2286q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":735};
const content = `<path class="rgjm2286q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:p-upper-case" {...props}></Icon>
