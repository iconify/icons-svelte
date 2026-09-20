<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg6azkrhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jg6azkrhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:id-card" {...props}></Icon>
