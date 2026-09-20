<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loc77xbtr.css';
import '../../css/d/d0ipc7b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="loc77xbtr"/><path class="d0ipc7b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:brg" {...props}></Icon>
