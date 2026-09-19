<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8q23kbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8q23kbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:border-style" {...props}></Icon>
