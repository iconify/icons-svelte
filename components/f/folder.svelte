<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgaqpcbiz.css';
import '../../css/l/lcaoj-wbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgaqpcbiz"/><path class="lcaoj-wbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:folder" {...props}></Icon>
