<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-u4b9bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-u4b9bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:hinduism-flat" {...props}></Icon>
