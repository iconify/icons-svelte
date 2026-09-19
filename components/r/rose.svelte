<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-a6_h5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="ln-a6_h5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:rose" {...props}></Icon>
