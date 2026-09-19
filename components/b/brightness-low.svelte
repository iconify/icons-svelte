<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed6yhd3rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ed6yhd3rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:brightness-low" {...props}></Icon>
