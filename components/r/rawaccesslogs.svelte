<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-5oytupx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="z-5oytupx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:rawaccesslogs" {...props}></Icon>
