<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-g2gdbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-g2gdbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish3-very-sad" {...props}></Icon>
