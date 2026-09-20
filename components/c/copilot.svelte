<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf7zolb1b.css';
import '../../css/l/l6ei140ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jf7zolb1b"/><path class="l6ei140ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:copilot" {...props}></Icon>
