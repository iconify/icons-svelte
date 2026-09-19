<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e26v0zbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e26v0zbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:grass" {...props}></Icon>
