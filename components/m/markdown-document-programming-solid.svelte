<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4dbs1bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u4dbs1bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:markdown-document-programming-solid" {...props}></Icon>
