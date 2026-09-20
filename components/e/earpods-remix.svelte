<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl-ucttbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cl-ucttbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:earpods-remix" {...props}></Icon>
