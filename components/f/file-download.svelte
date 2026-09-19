<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2n7cu74s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="v2n7cu74s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:file-download" {...props}></Icon>
