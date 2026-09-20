<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu6c_ub0k.css';
import '../../css/c/c0644sbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu6c_ub0k"/><path class="c0644sbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-square-search" {...props}></Icon>
