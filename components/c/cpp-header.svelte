<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn9o4mbwr.css';
import '../../css/b/bmx7xbb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tn9o4mbwr"/><path class="bmx7xbb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cpp-header" {...props}></Icon>
