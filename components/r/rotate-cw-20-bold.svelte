<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3_ihpb5f.css';
import '../../css/d/d3xqtkb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e3_ihpb5f"/><path class="d3xqtkb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-cw-20-bold" {...props}></Icon>
