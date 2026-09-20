<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwhco13bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="bwhco13bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file" {...props}></Icon>
