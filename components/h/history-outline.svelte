<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgl-lsb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kgl-lsb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:history-outline" {...props}></Icon>
