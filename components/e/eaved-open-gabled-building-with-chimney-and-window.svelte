<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2gvucboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e2gvucboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-open-gabled-building-with-chimney-and-window" {...props}></Icon>
