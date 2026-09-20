<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1m50d5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1m50d5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flip-horizontal-arrow-1-solid" {...props}></Icon>
