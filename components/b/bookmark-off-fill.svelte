<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9vgrzxot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9vgrzxot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bookmark-off-fill" {...props}></Icon>
