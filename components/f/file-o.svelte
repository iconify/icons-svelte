<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe3oz-bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oe3oz-bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-o" {...props}></Icon>
