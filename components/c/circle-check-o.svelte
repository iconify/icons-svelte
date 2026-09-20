<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v53dtq5ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v53dtq5ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:circle-check-o" {...props}></Icon>
