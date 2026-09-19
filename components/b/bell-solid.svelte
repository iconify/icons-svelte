<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd_488hbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd_488hbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-solid" {...props}></Icon>
