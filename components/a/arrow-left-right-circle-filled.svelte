<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgxy10d8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgxy10d8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-right-circle-filled" {...props}></Icon>
