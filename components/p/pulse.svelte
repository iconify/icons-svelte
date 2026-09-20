<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afxuf779n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="afxuf779n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:pulse" {...props}></Icon>
