<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y55p0-byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y55p0-byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-and-question-mark" {...props}></Icon>
