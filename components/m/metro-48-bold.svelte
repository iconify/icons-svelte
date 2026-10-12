<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_qf0abbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p_qf0abbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:metro-48-bold" {...props}></Icon>
