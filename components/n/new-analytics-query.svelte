<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx1wp0run.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sx1wp0run"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:new-analytics-query" {...props}></Icon>
