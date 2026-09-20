<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkww0n1py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lkww0n1py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-held-remix" {...props}></Icon>
