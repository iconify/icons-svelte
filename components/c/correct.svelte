<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at03s0y1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="at03s0y1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:correct" {...props}></Icon>
