<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dddim5jqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dddim5jqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:command-flat" {...props}></Icon>
