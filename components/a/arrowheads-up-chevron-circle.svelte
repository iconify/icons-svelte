<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kucpko94k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kucpko94k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-chevron-circle" {...props}></Icon>
