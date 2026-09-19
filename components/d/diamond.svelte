<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlyqhbbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qlyqhbbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:diamond" {...props}></Icon>
