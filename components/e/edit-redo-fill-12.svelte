<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umnnux3_u.css';
import '../../css/m/mgoapachr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="umnnux3_u"/><path class="mgoapachr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-redo-fill-12" {...props}></Icon>
