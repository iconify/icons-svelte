<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzf6qpbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzf6qpbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:announcement-alt-01-filled" {...props}></Icon>
