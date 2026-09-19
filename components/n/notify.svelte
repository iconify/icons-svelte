<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7va7rbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":679,"height":680};
const content = `<path class="d7va7rbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:notify" {...props}></Icon>
