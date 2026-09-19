<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6f-icc4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q6f-icc4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:easel" {...props}></Icon>
