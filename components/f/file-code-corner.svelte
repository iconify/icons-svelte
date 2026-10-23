<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmdyl_bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmdyl_bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-code-corner" {...props}></Icon>
