<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfh0oxb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pfh0oxb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:color-picker-solid" {...props}></Icon>
