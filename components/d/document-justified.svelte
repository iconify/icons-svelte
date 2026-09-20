<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_a5gssuo.css';
import '../../css/j/jtowsomii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<defs><path id="SVGVatqZbTj" class="g_a5gssuo"/></defs><g class="jtowsomii"><use href="#SVGVatqZbTj"/><use href="#SVGVatqZbTj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:document-justified" {...props}></Icon>
