<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp7g_qljv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wp7g_qljv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:license" {...props}></Icon>
