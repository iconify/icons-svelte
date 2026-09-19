<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdaqj9bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cdaqj9bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-squint-tears" {...props}></Icon>
