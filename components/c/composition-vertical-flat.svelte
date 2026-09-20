<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8v6whbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z8v6whbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:composition-vertical-flat" {...props}></Icon>
