<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz-9m7b0m.css';
import '../../css/o/oi5x-1v0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz-9m7b0m"/><path class="oi5x-1v0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-checked-filled" {...props}></Icon>
