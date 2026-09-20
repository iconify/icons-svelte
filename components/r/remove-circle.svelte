<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir8a84vmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ir8a84vmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remove-circle" {...props}></Icon>
