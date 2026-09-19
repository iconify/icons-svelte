<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5aho55cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1216,"height":2016};
const content = `<path class="h5aho55cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:door-open" {...props}></Icon>
