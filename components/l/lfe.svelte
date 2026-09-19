<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0a_jacfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":434,"height":512};
const content = `<path clip-rule="evenodd" class="p0a_jacfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lfe" {...props}></Icon>
