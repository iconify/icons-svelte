<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxqyoy7th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nxqyoy7th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting" {...props}></Icon>
