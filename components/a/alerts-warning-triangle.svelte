<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbdo17bye.css';
import '../../css/e/eag0spbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbdo17bye"/><path class="eag0spbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:alerts-warning-triangle" {...props}></Icon>
