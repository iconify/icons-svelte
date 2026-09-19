<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa322bcas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fa322bcas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:euro-outline" {...props}></Icon>
