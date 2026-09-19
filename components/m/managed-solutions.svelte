<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzwywtzpa.css';
import '../../css/x/xvq7pg0gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dzwywtzpa"/><path class="xvq7pg0gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:managed-solutions" {...props}></Icon>
