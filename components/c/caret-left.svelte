<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv-fi9ely.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv-fi9ely"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:caret-left" {...props}></Icon>
