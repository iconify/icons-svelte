<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx6x9k59k.css';
import '../../css/z/zoxpwbb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx6x9k59k"/><path class="zoxpwbb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-plus-corner-filled" {...props}></Icon>
