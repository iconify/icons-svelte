<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cui9sabnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cui9sabnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:folder" {...props}></Icon>
