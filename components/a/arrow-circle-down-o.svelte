<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51w7z-wj.css';
import '../../css/e/edf-x6box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j51w7z-wj"/><path class="edf-x6box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrow-circle-down-o" {...props}></Icon>
