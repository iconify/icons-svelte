<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifuufmagt.css';
import '../../css/u/ubv5z7b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="ifuufmagt"/><path class="ubv5z7b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:huff" {...props}></Icon>
