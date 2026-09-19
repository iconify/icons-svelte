<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9l9zbzr.css';
import '../../css/g/gjykr6brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aw9l9zbzr"/><path class="gjykr6brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:result-draft" {...props}></Icon>
