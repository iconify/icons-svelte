<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-jk7uwey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z-jk7uwey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-left-bold" {...props}></Icon>
