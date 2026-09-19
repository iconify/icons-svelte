<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz8ykxbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mz8ykxbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:incomplete-cancel" {...props}></Icon>
