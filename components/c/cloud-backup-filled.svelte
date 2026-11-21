<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxh80gbuf.css';
import '../../css/f/fj4fd9bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxh80gbuf"/><path class="fj4fd9bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-backup-filled" {...props}></Icon>
