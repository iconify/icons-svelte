<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3lgamtva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="e3lgamtva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chair" {...props}></Icon>
