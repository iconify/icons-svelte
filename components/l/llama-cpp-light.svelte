<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etk58nhhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etk58nhhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:llama-cpp-light" {...props}></Icon>
