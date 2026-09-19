<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi2zpy8jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bi2zpy8jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fork-spoon" {...props}></Icon>
