<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d13zbfbdn.css';
import '../../css/x/xyyi6pxjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d13zbfbdn"/><path class="xyyi6pxjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-from-library-fill" {...props}></Icon>
