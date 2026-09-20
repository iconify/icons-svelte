<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0b3sfbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n0b3sfbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:office-building-1" {...props}></Icon>
