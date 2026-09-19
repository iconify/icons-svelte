<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i43ht4usc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i43ht4usc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plug-fill" {...props}></Icon>
