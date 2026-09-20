<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cce-x1b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cce-x1b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:play-stroke-16" {...props}></Icon>
