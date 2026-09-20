<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9-0loj0c.css';
import '../../css/c/cl9-c2b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9-0loj0c"/><path class="cl9-c2b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:code-yellow" {...props}></Icon>
