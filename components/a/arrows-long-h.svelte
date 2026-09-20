<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd9qbabfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jd9qbabfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrows-long-h" {...props}></Icon>
