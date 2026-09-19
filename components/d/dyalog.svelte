<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1ebpz8ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":470,"height":512};
const content = `<path class="i1ebpz8ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dyalog" {...props}></Icon>
