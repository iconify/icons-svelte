<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4se2mm0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f4se2mm0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:programclose" {...props}></Icon>
