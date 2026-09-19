<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8tv-ebop.css';
import '../../css/x/xvqdfg4fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8tv-ebop"/><path class="xvqdfg4fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:checkbox-checked" {...props}></Icon>
