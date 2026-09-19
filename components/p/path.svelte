<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1i54mbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="q1i54mbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:path" {...props}></Icon>
