<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-y74dbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h-y74dbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brain-remix" {...props}></Icon>
