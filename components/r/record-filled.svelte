<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uesya8onb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uesya8onb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:record-filled" {...props}></Icon>
