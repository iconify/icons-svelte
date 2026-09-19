<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws9aemb-h.css';
import '../../css/m/mkjrunb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ws9aemb-h"/><path class="mkjrunb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:crowd-report-filled" {...props}></Icon>
