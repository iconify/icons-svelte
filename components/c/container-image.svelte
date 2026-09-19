<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5iso1b0c.css';
import '../../css/u/ul7vggbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5iso1b0c"/><path class="ul7vggbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:container-image" {...props}></Icon>
