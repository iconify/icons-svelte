<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skw6qbb9b.css';
import '../../css/z/ztdjq8bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="skw6qbb9b"/><path class="ztdjq8bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribution-board-20-bold" {...props}></Icon>
