<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioxvljb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ioxvljb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:absolute-position" {...props}></Icon>
