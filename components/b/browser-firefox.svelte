<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0aiwjbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0aiwjbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:browser-firefox" {...props}></Icon>
