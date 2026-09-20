<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ql-2g6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n7ql-2g6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-2-remix" {...props}></Icon>
