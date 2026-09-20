<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9li8s_7q.css';
import '../../css/e/ex0rr4b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9li8s_7q"/><path class="ex0rr4b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:craco" {...props}></Icon>
