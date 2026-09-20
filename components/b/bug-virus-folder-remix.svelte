<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7vjquc4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b7vjquc4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-virus-folder-remix" {...props}></Icon>
