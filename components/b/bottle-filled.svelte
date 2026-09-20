<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-2s2sb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-2s2sb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bottle-filled" {...props}></Icon>
