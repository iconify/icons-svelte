<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jcd1ec3dy.css';
import '../../css/z/zeo2ynvmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="jcd1ec3dy"/><path class="zeo2ynvmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:open-file-filled" {...props}></Icon>
