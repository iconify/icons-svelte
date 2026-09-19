<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5oyh1b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q5oyh1b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:clover" {...props}></Icon>
