<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spm6x1x7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spm6x1x7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:bazel" {...props}></Icon>
