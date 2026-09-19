<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ok4bcnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d2ok4bcnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:rectangle" {...props}></Icon>
