<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9b_1cblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u9b_1cblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:handset" {...props}></Icon>
