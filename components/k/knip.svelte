<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adfsecccc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="adfsecccc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:knip" {...props}></Icon>
