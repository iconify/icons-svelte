<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv39uello.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gv39uello"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bone" {...props}></Icon>
