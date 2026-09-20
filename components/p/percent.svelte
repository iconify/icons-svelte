<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ewivb3f.css';
import '../../css/q/q7f-xhboq.css';
import '../../css/z/z6-akobdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9ewivb3f"/><path class="q7f-xhboq"/><path class="z6-akobdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:percent" {...props}></Icon>
