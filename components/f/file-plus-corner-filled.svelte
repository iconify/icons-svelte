<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6gs46bps.css';
import '../../css/f/fi3u09b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6gs46bps"/><path class="fi3u09b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-plus-corner-filled" {...props}></Icon>
