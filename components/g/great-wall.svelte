<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmkjt401p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lmkjt401p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:great-wall" {...props}></Icon>
