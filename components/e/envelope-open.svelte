<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpmku4bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tpmku4bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:envelope-open" {...props}></Icon>
