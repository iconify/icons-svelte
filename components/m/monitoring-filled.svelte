<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/c/c8_9t0b8w.css';
import '../../css/i/ikgnmspxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="c8_9t0b8w"/><path class="ikgnmspxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:monitoring-filled" {...props}></Icon>
