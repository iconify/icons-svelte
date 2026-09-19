<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1is9vb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1is9vb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-left-square-filled" {...props}></Icon>
