<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyglo22yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eyglo22yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:corner-lower-left" {...props}></Icon>
