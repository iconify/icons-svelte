<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss1lqj77n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ss1lqj77n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:paint-roll" {...props}></Icon>
