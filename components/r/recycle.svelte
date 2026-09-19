<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vexk7p94v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vexk7p94v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:recycle" {...props}></Icon>
