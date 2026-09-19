<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w81rfccet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w81rfccet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:home" {...props}></Icon>
