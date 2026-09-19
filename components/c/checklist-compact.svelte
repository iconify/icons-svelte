<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beavldbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="beavldbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:checklist-compact" {...props}></Icon>
