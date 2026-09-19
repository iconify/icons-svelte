<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofz5wxbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ofz5wxbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow" {...props}></Icon>
