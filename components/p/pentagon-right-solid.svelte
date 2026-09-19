<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef3j2cb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef3j2cb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-right-solid" {...props}></Icon>
