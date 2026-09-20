<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7-fi2btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f7-fi2btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:block-2" {...props}></Icon>
