<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0b5x4exe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f0b5x4exe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:new-file-solid" {...props}></Icon>
