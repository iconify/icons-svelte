<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85tckexn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f85tckexn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:power-generator" {...props}></Icon>
