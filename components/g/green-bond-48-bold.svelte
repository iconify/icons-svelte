<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj1y5cbbe.css';
import '../../css/j/j8h-reucj.css';
import '../../css/d/dit17kuus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="j8h-reucj"/><path class="dit17kuus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-bond-48-bold" {...props}></Icon>
