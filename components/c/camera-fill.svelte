<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1barb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bc1barb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-fill" {...props}></Icon>
