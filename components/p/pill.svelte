<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l98k7eboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l98k7eboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pill" {...props}></Icon>
