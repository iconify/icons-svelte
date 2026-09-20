<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro-7c5u2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ro-7c5u2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cube" {...props}></Icon>
