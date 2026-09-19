<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muwqqh8bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="muwqqh8bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-left-square-fill" {...props}></Icon>
