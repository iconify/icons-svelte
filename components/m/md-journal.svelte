<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm11y1rnv.css';
import '../../css/c/cmgsz-b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jm11y1rnv"/><path class="cmgsz-b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-journal" {...props}></Icon>
