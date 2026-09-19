<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6dm7wbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w6dm7wbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:map-center" {...props}></Icon>
