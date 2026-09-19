<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9x-l-zkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u9x-l-zkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:7-circle" {...props}></Icon>
