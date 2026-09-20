<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_p8eblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ja_p8eblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-divide-solid" {...props}></Icon>
