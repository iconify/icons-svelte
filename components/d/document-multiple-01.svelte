<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdp22ib8n.css';
import '../../css/s/sz152uiha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jdp22ib8n"/><path class="sz152uiha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-multiple-01" {...props}></Icon>
