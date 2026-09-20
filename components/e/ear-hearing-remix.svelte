<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb8c3rbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pb8c3rbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ear-hearing-remix" {...props}></Icon>
