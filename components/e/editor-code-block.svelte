<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xza3v1tkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xza3v1tkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-code-block" {...props}></Icon>
