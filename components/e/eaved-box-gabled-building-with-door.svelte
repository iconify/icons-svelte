<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dky4xzbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dky4xzbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-box-gabled-building-with-door" {...props}></Icon>
