<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgmhxkf8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zgmhxkf8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-text" {...props}></Icon>
