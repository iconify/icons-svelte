<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgs4tjchy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sgs4tjchy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:file-code-1-remix" {...props}></Icon>
