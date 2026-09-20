<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pys7aibts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pys7aibts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-remix" {...props}></Icon>
