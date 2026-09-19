<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjgpfbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxjgpfbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:flip-horizontal-filled" {...props}></Icon>
