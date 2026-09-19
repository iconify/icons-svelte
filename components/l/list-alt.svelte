<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6p5ah1gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6p5ah1gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:list-alt" {...props}></Icon>
