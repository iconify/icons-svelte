<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjty1rbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jjty1rbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:merge" {...props}></Icon>
