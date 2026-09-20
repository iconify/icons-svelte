<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvg7sdoku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":231};
const content = `<path class="dvg7sdoku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:expo" {...props}></Icon>
