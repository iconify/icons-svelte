<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le-81vboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="le-81vboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pin" {...props}></Icon>
