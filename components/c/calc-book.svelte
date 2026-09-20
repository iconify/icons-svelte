<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dadjwxblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dadjwxblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calc-book" {...props}></Icon>
