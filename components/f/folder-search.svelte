<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo0xyvbqi.css';
import '../../css/g/g5pmz6bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo0xyvbqi"/><path class="g5pmz6bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:folder-search" {...props}></Icon>
