<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wozebsbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":695,"height":717};
const content = `<path class="wozebsbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pencil" {...props}></Icon>
