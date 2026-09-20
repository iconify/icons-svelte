<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4hsm_bxh.css';
import '../../css/j/j51w7z-wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d4hsm_bxh"/><path class="j51w7z-wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-circle-down-o" {...props}></Icon>
