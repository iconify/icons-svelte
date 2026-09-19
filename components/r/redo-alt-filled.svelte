<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djbaptj0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djbaptj0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:redo-alt-filled" {...props}></Icon>
