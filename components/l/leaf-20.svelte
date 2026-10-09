<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyzs50b8b.css';
import '../../css/v/vceoc3bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fyzs50b8b"/><path class="vceoc3bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-20" {...props}></Icon>
