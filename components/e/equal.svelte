<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeo6qjb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jeo6qjb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:equal" {...props}></Icon>
