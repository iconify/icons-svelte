<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgvc7ymii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fgvc7ymii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:file-code-1-remix" {...props}></Icon>
