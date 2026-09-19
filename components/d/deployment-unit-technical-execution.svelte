<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewxs8lclm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ewxs8lclm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-unit-technical-execution" {...props}></Icon>
