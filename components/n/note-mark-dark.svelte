<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv33ksbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv33ksbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:note-mark-dark" {...props}></Icon>
