<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlh0h9bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":489,"height":628};
const content = `<path class="rlh0h9bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:next" {...props}></Icon>
