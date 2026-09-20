<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfl_0pbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mfl_0pbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:download-arrow-remix" {...props}></Icon>
