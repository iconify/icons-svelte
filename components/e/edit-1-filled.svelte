<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz9ip8bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz9ip8bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:edit-1-filled" {...props}></Icon>
