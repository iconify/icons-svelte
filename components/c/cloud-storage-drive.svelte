<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t800yyb2z.css';
import '../../css/e/e7w46bv7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t800yyb2z"/><path class="e7w46bv7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cloud-storage-drive" {...props}></Icon>
