<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9totb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co9totb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-txt-filled" {...props}></Icon>
