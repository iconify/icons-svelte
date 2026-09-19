<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo6ekxl-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="uo6ekxl-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:caret-up" {...props}></Icon>
