<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-p8bxbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p-p8bxbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cloud-download-remix" {...props}></Icon>
