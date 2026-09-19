<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfi3wizrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jfi3wizrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:list-view" {...props}></Icon>
