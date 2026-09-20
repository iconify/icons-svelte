<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-9o316jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k-9o316jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-expand-flat" {...props}></Icon>
