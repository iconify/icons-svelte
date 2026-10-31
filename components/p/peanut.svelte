<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u578mdyfv.css';
import '../../css/j/jflejabkx.css';
import '../../css/o/oy8ziy8su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u578mdyfv"/><path class="jflejabkx"/><path class="oy8ziy8su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:peanut" {...props}></Icon>
