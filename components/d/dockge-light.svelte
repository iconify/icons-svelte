<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atehkzbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="atehkzbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockge-light" {...props}></Icon>
