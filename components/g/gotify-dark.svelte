<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ees4jqgyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="ees4jqgyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotify-dark" {...props}></Icon>
