<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkk121bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mkk121bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gdb" {...props}></Icon>
