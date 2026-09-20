<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4dloeh4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l4dloeh4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pill" {...props}></Icon>
