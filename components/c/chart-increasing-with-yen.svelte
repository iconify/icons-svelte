<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynna6ub8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ynna6ub8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:chart-increasing-with-yen" {...props}></Icon>
