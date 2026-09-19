<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9_tcobxs.css';
import '../../css/f/fj4btac-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9_tcobxs"/><path class="fj4btac-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bookmark-alt-plus" {...props}></Icon>
