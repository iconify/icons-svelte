<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az-5w-ucj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="az-5w-ucj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:right-small" {...props}></Icon>
