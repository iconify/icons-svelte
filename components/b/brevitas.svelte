<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5c-3sjfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":240,"height":240};
const content = `<path class="c5c-3sjfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:brevitas" {...props}></Icon>
