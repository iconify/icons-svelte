<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnuiw5usx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gnuiw5usx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chatgpt-dark" {...props}></Icon>
