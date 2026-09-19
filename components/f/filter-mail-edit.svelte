<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6nl0kb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6nl0kb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:filter-mail-edit" {...props}></Icon>
