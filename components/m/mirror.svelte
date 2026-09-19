<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5z938glt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k5z938glt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:mirror" {...props}></Icon>
