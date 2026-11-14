<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k97snyb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k97snyb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-shared-03" {...props}></Icon>
