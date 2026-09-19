<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0egwfhfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g0egwfhfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:location" {...props}></Icon>
