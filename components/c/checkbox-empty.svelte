<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zowbxhbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zowbxhbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-empty" {...props}></Icon>
