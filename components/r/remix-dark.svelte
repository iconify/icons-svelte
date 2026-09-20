<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytk9vubnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":297};
const content = `<path class="ytk9vubnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:remix-dark" {...props}></Icon>
