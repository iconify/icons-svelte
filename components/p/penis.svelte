<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrj6w4b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hrj6w4b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:penis" {...props}></Icon>
