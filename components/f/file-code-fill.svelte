<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctylnj5jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctylnj5jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-code-fill" {...props}></Icon>
