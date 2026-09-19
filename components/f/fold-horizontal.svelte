<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npc8rjpju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npc8rjpju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:fold-horizontal" {...props}></Icon>
