<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etdkoebcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="etdkoebcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-walking-dashed-line-arrow-right" {...props}></Icon>
