<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdmmufb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(1.00302 0 0 1 -.05 0)" class="jdmmufb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:code-climate" {...props}></Icon>
