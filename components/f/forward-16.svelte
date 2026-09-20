<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws3c52ixo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ws3c52ixo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:forward-16" {...props}></Icon>
