<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy3dr47ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zy3dr47ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:c-header" {...props}></Icon>
