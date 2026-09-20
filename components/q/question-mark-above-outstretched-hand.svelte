<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgqu7acml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgqu7acml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:question-mark-above-outstretched-hand" {...props}></Icon>
