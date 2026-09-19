<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uihc5cbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uihc5cbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:fan" {...props}></Icon>
