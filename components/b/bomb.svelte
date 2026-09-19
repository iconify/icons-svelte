<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hryy9qzuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="hryy9qzuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bomb" {...props}></Icon>
