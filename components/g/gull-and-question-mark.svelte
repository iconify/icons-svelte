<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7piy7bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v7piy7bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gull-and-question-mark" {...props}></Icon>
