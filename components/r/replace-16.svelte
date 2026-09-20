<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feoxutb2p.css';
import '../../css/c/ce2rhacdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="feoxutb2p"/><path class="ce2rhacdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:replace-16" {...props}></Icon>
