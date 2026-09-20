<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-4e5pb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-4e5pb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:attic-1-filled" {...props}></Icon>
