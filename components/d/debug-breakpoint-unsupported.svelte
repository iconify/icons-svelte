<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ove_r8gba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ove_r8gba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-breakpoint-unsupported" {...props}></Icon>
