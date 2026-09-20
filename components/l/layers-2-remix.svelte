<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9mlwcbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u9mlwcbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layers-2-remix" {...props}></Icon>
