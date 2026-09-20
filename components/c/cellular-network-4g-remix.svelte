<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzdrmbgrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pzdrmbgrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cellular-network-4g-remix" {...props}></Icon>
