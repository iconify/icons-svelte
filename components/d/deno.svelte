<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdp1j7-gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hdp1j7-gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:deno" {...props}></Icon>
