<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbl0ijbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mbl0ijbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:chess-knight" {...props}></Icon>
