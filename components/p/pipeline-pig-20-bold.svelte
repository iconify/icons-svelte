<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3g6zbcc.css';
import '../../css/c/cbyfxzbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lw3g6zbcc"/><path class="cbyfxzbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-pig-20-bold" {...props}></Icon>
