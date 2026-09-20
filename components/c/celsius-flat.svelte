<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeka40byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aeka40byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:celsius-flat" {...props}></Icon>
