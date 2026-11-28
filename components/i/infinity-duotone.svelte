<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtsse_bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtsse_bfw primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:infinity-duotone" {...props}></Icon>
