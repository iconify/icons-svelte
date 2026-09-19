<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbfi2qb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jbfi2qb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:right-panel-open-filled" {...props}></Icon>
