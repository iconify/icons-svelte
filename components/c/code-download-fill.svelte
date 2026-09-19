<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmhge1brw.css';
import '../../css/t/t8uvlebro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmhge1brw"/><path class="t8uvlebro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:code-download-fill" {...props}></Icon>
