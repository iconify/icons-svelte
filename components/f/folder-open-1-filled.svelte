<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8u0u259p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8u0u259p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-open-1-filled" {...props}></Icon>
