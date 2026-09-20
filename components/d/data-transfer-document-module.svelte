<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1c6mcb8b.css';
import '../../css/f/fypyp2bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1c6mcb8b"/><path class="fypyp2bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-document-module" {...props}></Icon>
