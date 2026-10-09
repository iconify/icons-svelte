<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0pjpe9ss.css';
import '../../css/o/ols5a6b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w0pjpe9ss"/><path class="ols5a6b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-horizontal-20" {...props}></Icon>
