<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5izz9dil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5izz9dil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:figma-fill" {...props}></Icon>
