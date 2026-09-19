<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8b-mib4c.css';
import '../../css/v/vs9a-qkba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h8b-mib4c"/><path class="vs9a-qkba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-fill-12" {...props}></Icon>
