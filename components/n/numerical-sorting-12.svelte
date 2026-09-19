<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd8p0tzdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wd8p0tzdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:numerical-sorting-12" {...props}></Icon>
