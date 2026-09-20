<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4y2z7h4a.css';
import '../../css/a/akcuay_-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g4y2z7h4a"/><path class="akcuay_-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cloud" {...props}></Icon>
