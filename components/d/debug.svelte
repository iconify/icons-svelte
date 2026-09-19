<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en8l--6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="en8l--6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:debug" {...props}></Icon>
