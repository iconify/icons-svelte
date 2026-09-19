<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcc7plb6l.css';
import '../../css/r/rhcdyqe0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hcc7plb6l"/><path class="rhcdyqe0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-nutrition" {...props}></Icon>
