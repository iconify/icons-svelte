<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-0xczbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z-0xczbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:os2" {...props}></Icon>
