<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drdb5kbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="drdb5kbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cube-two" {...props}></Icon>
