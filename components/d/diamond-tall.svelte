<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oslo0obqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oslo0obqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:diamond-tall" {...props}></Icon>
