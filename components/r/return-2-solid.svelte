<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvi70vyqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xvi70vyqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:return-2-solid" {...props}></Icon>
