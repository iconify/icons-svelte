<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd_d6heja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd_d6heja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:layout-filled" {...props}></Icon>
