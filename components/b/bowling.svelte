<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu75xnflc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pu75xnflc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bowling" {...props}></Icon>
