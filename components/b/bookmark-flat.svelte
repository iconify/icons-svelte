<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzgxoj3mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nzgxoj3mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:bookmark-flat" {...props}></Icon>
