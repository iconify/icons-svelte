<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucnqb3dtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ucnqb3dtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-arrow-up" {...props}></Icon>
