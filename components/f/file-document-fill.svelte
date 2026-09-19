<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxhry76x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psxhry76x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-document-fill" {...props}></Icon>
